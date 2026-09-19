<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk_1jabpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk_1jabpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:go3" /></template>
