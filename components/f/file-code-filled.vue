<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj8qivbuk.css';
import '../../css/o/o3q91_but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj8qivbuk"/><path class="o3q91_but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-code-filled" /></template>
