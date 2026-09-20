<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7-1mk3gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t7-1mk3gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-fail-filled" /></template>
