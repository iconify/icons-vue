<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxbwy6b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxbwy6b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bollard" /></template>
