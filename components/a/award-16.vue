<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4npesb2t.css';
import '../../css/c/c6fjxyvsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w4npesb2t"/><path clip-rule="evenodd" class="c6fjxyvsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:award-16" /></template>
