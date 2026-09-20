<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1pgs7_hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1pgs7_hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:checklist-note-fill" /></template>
