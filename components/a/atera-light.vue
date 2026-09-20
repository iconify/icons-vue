<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phqk2vbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="phqk2vbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:atera-light" /></template>
