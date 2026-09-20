<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e65x3t4hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e65x3t4hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:cancel" /></template>
