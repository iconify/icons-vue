<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shd6ibcoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shd6ibcoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:focus-field-vertical" /></template>
