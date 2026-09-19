<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtl2wew-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtl2wew-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cobol" /></template>
