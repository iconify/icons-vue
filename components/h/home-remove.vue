<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgcuh9bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgcuh9bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-remove" /></template>
