<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reac64byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="reac64byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:glide" /></template>
