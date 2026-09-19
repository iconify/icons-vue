<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2fch2n5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2fch2n5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:line-spacing-alt-filled" /></template>
