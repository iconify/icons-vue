<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e09nf7bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e09nf7bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-import" /></template>
