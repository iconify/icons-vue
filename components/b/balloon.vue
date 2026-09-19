<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2lrtvbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n2lrtvbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:balloon" /></template>
