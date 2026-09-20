<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0xwgf8fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0xwgf8fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:brush5-filled" /></template>
