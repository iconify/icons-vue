<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcpe4647d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcpe4647d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btcst" /></template>
