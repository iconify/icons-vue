<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn54w67rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pn54w67rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-upload" /></template>
