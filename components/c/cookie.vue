<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bls7y0bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bls7y0bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cookie" /></template>
