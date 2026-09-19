<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm0-dsbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pm0-dsbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fantom" /></template>
