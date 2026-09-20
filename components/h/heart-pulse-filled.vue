<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr36w-16i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mr36w-16i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-pulse-filled" /></template>
