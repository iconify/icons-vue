<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2bken2kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u2bken2kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:feelgood" /></template>
