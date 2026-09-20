<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwkhj_byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zwkhj_byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cloud-16" /></template>
