<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh5ri3jtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uh5ri3jtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:fast-forward-filled" /></template>
