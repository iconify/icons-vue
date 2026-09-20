<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq403ub1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq403ub1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:krl" /></template>
