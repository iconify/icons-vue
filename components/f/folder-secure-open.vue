<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4w-vcsn.css';
import '../../css/w/w7jijrg7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ov4w-vcsn"/><path class="w7jijrg7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-secure-open" /></template>
