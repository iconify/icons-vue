<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nltrybcel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nltrybcel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:curtains" /></template>
