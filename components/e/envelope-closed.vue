<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb61fbftd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nb61fbftd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:envelope-closed" /></template>
