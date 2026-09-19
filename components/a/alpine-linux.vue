<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojbpt1xwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojbpt1xwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:alpine-linux" /></template>
