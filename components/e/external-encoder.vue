<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cff9kyb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cff9kyb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:external-encoder" /></template>
