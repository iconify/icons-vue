<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhllcmz3q.css';
import '../../css/g/g11id0bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fhllcmz3q"/><path class="g11id0bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:add-files" /></template>
