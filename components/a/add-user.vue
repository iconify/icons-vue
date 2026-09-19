<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3na2nb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3na2nb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:add-user" /></template>
