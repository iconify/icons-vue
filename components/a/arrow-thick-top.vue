<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw-jh6bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nw-jh6bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-thick-top" /></template>
