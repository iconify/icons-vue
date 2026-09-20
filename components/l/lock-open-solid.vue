<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4jt-mads.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4jt-mads"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:lock-open-solid" /></template>
