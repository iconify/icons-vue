<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic72lyaaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":46,"height":80};
const content = `<path class="ic72lyaaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:draghandle" /></template>
