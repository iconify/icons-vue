<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g036ecckr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g036ecckr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:clipboard" /></template>
