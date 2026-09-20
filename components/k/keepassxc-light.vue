<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7b2ktb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h7b2ktb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keepassxc-light" /></template>
