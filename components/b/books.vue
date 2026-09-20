<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo-i2pb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo-i2pb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:books" /></template>
