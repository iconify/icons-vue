<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf8ho-irp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zf8ho-irp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:keyboard-outline" /></template>
