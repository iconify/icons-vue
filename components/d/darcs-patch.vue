<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7wdktbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7wdktbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:darcs-patch" /></template>
