<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fopn9jr3y.css';
import '../../css/a/a2_u8gbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fopn9jr3y"/><path class="a2_u8gbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-x-corner-filled" /></template>
