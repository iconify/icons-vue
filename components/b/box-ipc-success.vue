<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm_2zebzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hm_2zebzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:box-ipc-success" /></template>
