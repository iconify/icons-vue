<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntcc_ys2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntcc_ys2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:dropbox" /></template>
