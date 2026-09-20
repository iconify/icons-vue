<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lff1pxbum.css';
import '../../css/o/ob4ovv27x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lff1pxbum"/><path class="ob4ovv27x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:lock-open" /></template>
