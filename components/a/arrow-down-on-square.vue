<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgn1g8e1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgn1g8e1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-down-on-square" /></template>
