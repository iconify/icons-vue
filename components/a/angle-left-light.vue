<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdiinzzdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdiinzzdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:angle-left-light" /></template>
