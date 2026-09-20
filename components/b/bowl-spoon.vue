<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isyk61bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isyk61bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bowl-spoon" /></template>
