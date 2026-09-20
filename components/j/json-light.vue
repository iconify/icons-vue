<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-h0w2bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-h0w2bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:json-light" /></template>
