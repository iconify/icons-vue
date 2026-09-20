<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_wxps6fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g_wxps6fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-jpg-filled" /></template>
