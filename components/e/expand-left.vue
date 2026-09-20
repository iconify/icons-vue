<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aze3fnbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aze3fnbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:expand-left" /></template>
