<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlm58cv6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nlm58cv6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:locomotive" /></template>
