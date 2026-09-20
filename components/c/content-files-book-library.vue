<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7quqgbjv.css';
import '../../css/s/s1tnk0x5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y7quqgbjv"/><path class="s1tnk0x5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-book-library" /></template>
