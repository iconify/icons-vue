<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncwk-2y5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ncwk-2y5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-photoshop" /></template>
