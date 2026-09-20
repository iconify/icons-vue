<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqzupl6gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqzupl6gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:controller-circle-down" /></template>
