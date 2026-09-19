<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo2e3-i0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="eo2e3-i0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-asterisk-filled" /></template>
