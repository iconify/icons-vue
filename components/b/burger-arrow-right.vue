<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuqlkybfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuqlkybfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-arrow-right" /></template>
