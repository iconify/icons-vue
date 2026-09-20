<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od_856e-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od_856e-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-drop-down" /></template>
