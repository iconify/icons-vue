<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfcmqtp3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfcmqtp3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:hockey-mask-solid" /></template>
