<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my-q2jn-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my-q2jn-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:link-variant-remove" /></template>
