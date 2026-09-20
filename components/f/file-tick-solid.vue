<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3tb05bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z3tb05bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:file-tick-solid" /></template>
