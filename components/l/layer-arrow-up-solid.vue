<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo9hxn6zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo9hxn6zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layer-arrow-up-solid" /></template>
