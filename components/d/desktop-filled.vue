<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an2x7zf5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an2x7zf5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:desktop-filled" /></template>
