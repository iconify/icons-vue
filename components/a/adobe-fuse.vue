<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9iipm8aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="c9iipm8aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-fuse" /></template>
