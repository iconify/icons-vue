<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a30lnybhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a30lnybhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:envelope-check-bold" /></template>
