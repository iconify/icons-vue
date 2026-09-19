<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cczraob2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cczraob2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-train" /></template>
