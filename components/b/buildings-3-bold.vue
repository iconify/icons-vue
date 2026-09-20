<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf-ow3pxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf-ow3pxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-3-bold" /></template>
