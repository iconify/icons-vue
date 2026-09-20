<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk34lgb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk34lgb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contrast-drop-2-fill" /></template>
