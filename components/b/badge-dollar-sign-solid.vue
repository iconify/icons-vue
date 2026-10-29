<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc4nkls7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc4nkls7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-dollar-sign-solid" /></template>
