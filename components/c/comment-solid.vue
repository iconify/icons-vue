<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plqtlgbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plqtlgbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:comment-solid" /></template>
