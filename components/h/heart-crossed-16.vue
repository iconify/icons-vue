<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm3r0-bhi.css';
import '../../css/p/pyjnocccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wm3r0-bhi"/><path clip-rule="evenodd" class="pyjnocccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:heart-crossed-16" /></template>
