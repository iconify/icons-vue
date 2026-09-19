<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhidz8epn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bhidz8epn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:macvim" /></template>
