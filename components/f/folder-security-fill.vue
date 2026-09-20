<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p226ibona.css';
import '../../css/d/d8x-s61pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p226ibona"/><path class="d8x-s61pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-security-fill" /></template>
