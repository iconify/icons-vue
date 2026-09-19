<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr6pc4b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zr6pc4b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:diagonal-cross-small" /></template>
