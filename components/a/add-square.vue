<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1pimjbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1pimjbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:add-square" /></template>
