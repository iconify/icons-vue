<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7d75gb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e7d75gb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-versions" /></template>
