<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifozqccno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ifozqccno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:file-code" /></template>
