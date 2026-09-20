<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unav5rb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="unav5rb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubetail-dark" /></template>
