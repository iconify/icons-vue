<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl48nf4cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl48nf4cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:confirmations-0-outline" /></template>
