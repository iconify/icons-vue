<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fstfmcwnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fstfmcwnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-server" /></template>
