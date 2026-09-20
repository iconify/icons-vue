<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6tugsbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z6tugsbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:machine-c-filled" /></template>
