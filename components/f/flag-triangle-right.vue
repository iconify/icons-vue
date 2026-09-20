<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjeytpgtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjeytpgtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:flag-triangle-right" /></template>
