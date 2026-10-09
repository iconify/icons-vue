<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbx5zccce.css';
import '../../css/z/zrqlkvb4c.css';
import '../../css/w/w-8r-b8kp.css';
import '../../css/t/tna6zhb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="zrqlkvb4c"/><path class="w-8r-b8kp"/><path class="tna6zhb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-snowflake-20" /></template>
