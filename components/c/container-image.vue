<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd1pfnb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vd1pfnb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:container-image" /></template>
