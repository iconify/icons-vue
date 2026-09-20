<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffuts4bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffuts4bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down-right-square-filled" /></template>
