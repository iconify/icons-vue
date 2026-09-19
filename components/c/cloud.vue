<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahih-gn5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ahih-gn5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:cloud" /></template>
