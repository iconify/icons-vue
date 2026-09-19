<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gum74vxer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gum74vxer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:flag-16-solid" /></template>
