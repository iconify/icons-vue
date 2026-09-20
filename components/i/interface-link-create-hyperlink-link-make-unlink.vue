<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r--l4krnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r--l4krnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-link-create-hyperlink-link-make-unlink" /></template>
