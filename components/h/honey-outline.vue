<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfy9ylpub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfy9ylpub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:honey-outline" /></template>
