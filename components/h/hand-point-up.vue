<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs721ibcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bs721ibcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:hand-point-up" /></template>
