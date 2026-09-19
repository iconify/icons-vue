<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va4lsmbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="va4lsmbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-five-filled" /></template>
