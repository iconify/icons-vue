<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vti7wdbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vti7wdbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:building1-filled" /></template>
