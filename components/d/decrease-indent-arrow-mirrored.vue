<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x42emccsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x42emccsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:decrease-indent-arrow-mirrored" /></template>
