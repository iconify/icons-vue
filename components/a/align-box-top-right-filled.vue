<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg5kujbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg5kujbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-top-right-filled" /></template>
