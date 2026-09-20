<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0w3bmbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0w3bmbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bat" /></template>
