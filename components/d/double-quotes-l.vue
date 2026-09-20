<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2wxqbc6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2wxqbc6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:double-quotes-l" /></template>
