<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4yobrbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4yobrbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:carton" /></template>
