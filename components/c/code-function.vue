<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luj_xzb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="luj_xzb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:code-function" /></template>
