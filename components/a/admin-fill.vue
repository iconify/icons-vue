<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh5iqbbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh5iqbbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:admin-fill" /></template>
