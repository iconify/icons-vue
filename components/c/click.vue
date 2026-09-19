<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj2dy6ioy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yj2dy6ioy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:click" /></template>
