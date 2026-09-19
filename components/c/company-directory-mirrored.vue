<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trg52ugic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="trg52ugic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:company-directory-mirrored" /></template>
