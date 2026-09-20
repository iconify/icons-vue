<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iezvbobgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="iezvbobgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-new" /></template>
