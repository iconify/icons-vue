<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fky8ubc-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fky8ubc-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-transfer-v-filled" /></template>
