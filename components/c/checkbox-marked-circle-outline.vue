<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9bnolcdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9bnolcdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbox-marked-circle-outline" /></template>
