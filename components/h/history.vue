<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekry2eb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ekry2eb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:history" /></template>
