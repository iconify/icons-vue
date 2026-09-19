<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6nlfmbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p6nlfmbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:file-s-q-l" /></template>
