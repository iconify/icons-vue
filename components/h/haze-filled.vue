<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayuyt_49f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ayuyt_49f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:haze-filled" /></template>
