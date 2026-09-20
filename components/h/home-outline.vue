<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebjckr-mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebjckr-mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-outline" /></template>
