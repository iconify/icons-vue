<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_mzvy6rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x_mzvy6rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:close-small-16" /></template>
