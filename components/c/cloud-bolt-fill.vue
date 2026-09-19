<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdsnvn27d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cdsnvn27d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-bolt-fill" /></template>
