<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af0ksw-nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="af0ksw-nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gauss" /></template>
