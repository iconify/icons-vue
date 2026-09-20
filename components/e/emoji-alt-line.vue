<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk_56sbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_56sbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:emoji-alt-line" /></template>
