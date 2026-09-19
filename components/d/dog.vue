<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wes1wgtwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wes1wgtwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:dog" /></template>
