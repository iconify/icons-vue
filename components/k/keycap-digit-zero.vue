<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw6ff4bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="iw6ff4bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-zero" /></template>
