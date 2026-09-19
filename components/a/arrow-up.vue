<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar3ql4bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar3ql4bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:arrow-up" /></template>
