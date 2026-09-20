<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh3kbwobr.css';
import '../../css/a/a321_xb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh3kbwobr"/><path clip-rule="evenodd" class="a321_xb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-date-solid" /></template>
