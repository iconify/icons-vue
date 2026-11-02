<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt0n_4ynm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt0n_4ynm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-edit-fill" /></template>
