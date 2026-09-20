<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3jifacya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n3jifacya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-cdr-filled" /></template>
