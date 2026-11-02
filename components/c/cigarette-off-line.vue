<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zljs9gavt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zljs9gavt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cigarette-off-line" /></template>
