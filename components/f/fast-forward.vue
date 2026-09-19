<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za43vpktg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za43vpktg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:fast-forward" /></template>
