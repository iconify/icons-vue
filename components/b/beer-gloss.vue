<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0x6dkb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0x6dkb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:beer-gloss" /></template>
