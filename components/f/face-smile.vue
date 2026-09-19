<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyoi2_bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyoi2_bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:face-smile" /></template>
