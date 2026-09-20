<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtf-8o_kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wtf-8o_kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-rain" /></template>
