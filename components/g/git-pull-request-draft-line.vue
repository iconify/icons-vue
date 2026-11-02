<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2wim-bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2wim-bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-draft-line" /></template>
