<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6g_i0b7t.css';
import '../../css/t/tt34x7bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6g_i0b7t"/><path class="tt34x7bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btcp" /></template>
