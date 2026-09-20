<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txfrc-r3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="txfrc-r3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homer-dark" /></template>
