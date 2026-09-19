<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvl9xpv9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pvl9xpv9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-merge-left" /></template>
