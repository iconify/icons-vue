<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7p7ftetp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z7p7ftetp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-bottom-right-beside-arrow-bottom-left-above-arrow-top-right-beside-arrow-top-left" /></template>
