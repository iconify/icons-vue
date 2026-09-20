<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9cykllwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i9cykllwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:live-preview" /></template>
