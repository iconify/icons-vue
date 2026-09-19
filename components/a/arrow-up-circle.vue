<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhv0vbuyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhv0vbuyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-circle" /></template>
