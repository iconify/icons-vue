<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y61lkwrsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y61lkwrsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-smile-beam" /></template>
