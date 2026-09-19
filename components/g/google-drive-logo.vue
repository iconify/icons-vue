<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs39i-btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qs39i-btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:google-drive-logo" /></template>
