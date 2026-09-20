<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-v6niwrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="m-v6niwrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-download-list" /></template>
