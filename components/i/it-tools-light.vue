<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab7nlyb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ab7nlyb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:it-tools-light" /></template>
