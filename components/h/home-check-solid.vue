<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr8e64lzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr8e64lzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:home-check-solid" /></template>
