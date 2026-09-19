<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5haedcuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5haedcuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lilypond" /></template>
