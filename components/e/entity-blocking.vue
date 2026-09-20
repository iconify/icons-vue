<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk7rb9bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bk7rb9bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:entity-blocking" /></template>
