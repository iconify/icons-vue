<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsr9job0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsr9job0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubetail-light" /></template>
