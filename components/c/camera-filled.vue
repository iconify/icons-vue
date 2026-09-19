<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s07htpbtb.css';
import '../../css/c/cdmk0wbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s07htpbtb"/><path class="cdmk0wbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-filled" /></template>
