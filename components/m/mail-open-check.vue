<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnrfv2bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnrfv2bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mail-open-check" /></template>
