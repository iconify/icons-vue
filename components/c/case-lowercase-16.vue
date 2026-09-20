<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqcyy616u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dqcyy616u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:case-lowercase-16" /></template>
