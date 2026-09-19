<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6fy1yokr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6fy1yokr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:lightning-solid" /></template>
