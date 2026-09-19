<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-cro6xfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-cro6xfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:go" /></template>
