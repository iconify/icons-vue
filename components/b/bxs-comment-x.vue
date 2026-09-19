<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7_eucm9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7_eucm9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-comment-x" /></template>
