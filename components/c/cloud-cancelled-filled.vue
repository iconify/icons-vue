<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbc2u206l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bbc2u206l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-cancelled-filled" /></template>
