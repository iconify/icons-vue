<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkrkz-bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkrkz-bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fountain" /></template>
