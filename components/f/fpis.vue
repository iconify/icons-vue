<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx4e6vbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sx4e6vbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fpis" /></template>
