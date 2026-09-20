<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz2m8acdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="bz2m8acdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-down" /></template>
