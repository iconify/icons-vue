<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbf3xmb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbf3xmb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:credit-card-check" /></template>
