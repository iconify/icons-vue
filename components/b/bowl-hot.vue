<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxzi38pia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxzi38pia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bowl-hot" /></template>
