<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g45yh2d2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g45yh2d2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-edit-outline" /></template>
