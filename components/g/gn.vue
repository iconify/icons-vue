<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylhcwq4-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ylhcwq4-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gn" /></template>
