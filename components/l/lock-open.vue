<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvwi7cb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvwi7cb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:lock-open" /></template>
