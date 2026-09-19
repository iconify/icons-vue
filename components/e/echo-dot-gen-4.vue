<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh4duubkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh4duubkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-dot-gen-4" /></template>
