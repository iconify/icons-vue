<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdt2tgb-r.css';
import '../../css/o/o922f4zod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vdt2tgb-r"/><path class="o922f4zod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calagopus-dark" /></template>
