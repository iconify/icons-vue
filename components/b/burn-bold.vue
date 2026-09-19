<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1kl_f1gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="k1kl_f1gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:burn-bold" /></template>
