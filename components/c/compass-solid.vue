<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxk-h-u3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxk-h-u3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:compass-solid" /></template>
