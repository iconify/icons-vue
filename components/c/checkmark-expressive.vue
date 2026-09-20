<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsfevtbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsfevtbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:checkmark-expressive" /></template>
