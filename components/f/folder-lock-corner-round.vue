<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn2_ctb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn2_ctb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-lock-corner-round" /></template>
