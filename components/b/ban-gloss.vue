<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds-3ltbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds-3ltbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ban-gloss" /></template>
