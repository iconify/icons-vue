<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sot6zfbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sot6zfbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:creative-commons-by" /></template>
