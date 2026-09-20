<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj0fh1bfy.css';
import '../../css/d/dko5xdvrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj0fh1bfy"/><path class="dko5xdvrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bluetooth-transfer-bold" /></template>
