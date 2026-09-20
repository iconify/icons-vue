<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgsw9d_7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bgsw9d_7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:function-curve-16" /></template>
