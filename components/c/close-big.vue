<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqy8bbbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqy8bbbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:close-big" /></template>
