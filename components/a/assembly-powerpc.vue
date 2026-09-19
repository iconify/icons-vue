<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blumpz5xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blumpz5xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-powerpc" /></template>
