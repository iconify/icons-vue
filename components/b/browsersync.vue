<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn4aefjsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":512};
const content = `<path class="tn4aefjsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:browsersync" /></template>
