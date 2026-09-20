<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a61m6fb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a61m6fb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:copy-to-clipboard" /></template>
