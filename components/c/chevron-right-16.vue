<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-_8fx3xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o-_8fx3xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-right-16" /></template>
