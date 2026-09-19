<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vele90bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vele90bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fingerprint-alt" /></template>
