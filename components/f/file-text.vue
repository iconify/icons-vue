<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbiht5bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tbiht5bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:file-text" /></template>
