<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p97i2jbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="p97i2jbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:helmet-safety-1" /></template>
