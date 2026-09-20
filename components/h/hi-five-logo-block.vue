<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_49-ccls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_49-ccls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:hi-five-logo-block" /></template>
