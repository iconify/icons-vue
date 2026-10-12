<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbw2wbk-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbw2wbk-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:glasses-filled" /></template>
