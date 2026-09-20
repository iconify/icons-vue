<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adudr_bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="adudr_bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-up-right-16" /></template>
