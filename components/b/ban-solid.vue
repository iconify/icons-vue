<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0r3kmi5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k0r3kmi5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:ban-solid" /></template>
