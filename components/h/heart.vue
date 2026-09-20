<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk6bg3bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk6bg3bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart" /></template>
