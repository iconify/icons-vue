<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2poz0bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2poz0bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dropbox-dark" /></template>
