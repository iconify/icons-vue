<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1weh2cbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1weh2cbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-distribute-end-fill" /></template>
