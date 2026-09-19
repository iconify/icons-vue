<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzl-5ovtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bzl-5ovtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:comment" /></template>
