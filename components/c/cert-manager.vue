<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za7xkl_6x.css';
import '../../css/x/xd0ybnb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="za7xkl_6x"/><path class="xd0ybnb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cert-manager" /></template>
