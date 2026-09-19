<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ect9myiif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ect9myiif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:child" /></template>
