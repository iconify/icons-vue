<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4v56n5fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4v56n5fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-2-line" /></template>
