<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anh9su9vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anh9su9vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clovalink" /></template>
