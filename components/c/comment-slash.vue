<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-og96_om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-og96_om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-slash" /></template>
