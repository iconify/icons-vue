<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0t5hu09k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k0t5hu09k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:basic-memory" /></template>
