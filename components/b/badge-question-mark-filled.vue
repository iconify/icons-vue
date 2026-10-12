<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_gkf5rlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_gkf5rlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-question-mark-filled" /></template>
