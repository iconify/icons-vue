<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la_vh3d1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="la_vh3d1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:double-vertical-bar-filled" /></template>
