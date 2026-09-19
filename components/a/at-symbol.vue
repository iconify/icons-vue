<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivs71aced.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivs71aced"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:at-symbol" /></template>
