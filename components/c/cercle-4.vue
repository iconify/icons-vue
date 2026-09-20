<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_h9vnu3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n_h9vnu3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cercle-4" /></template>
