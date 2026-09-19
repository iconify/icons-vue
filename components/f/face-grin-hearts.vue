<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnisfbc2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rnisfbc2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-grin-hearts" /></template>
