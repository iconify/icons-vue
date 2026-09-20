<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyhafj-ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyhafj-ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-h-diamond-solid" /></template>
