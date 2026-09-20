<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn4xu6bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn4xu6bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:expand-down-stop-light" /></template>
