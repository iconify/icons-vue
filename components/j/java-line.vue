<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uezf65v5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uezf65v5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:java-line" /></template>
