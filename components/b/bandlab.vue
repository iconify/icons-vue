<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_5v0uz2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_5v0uz2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bandlab" /></template>
