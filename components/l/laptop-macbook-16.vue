<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr_nvx8tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xr_nvx8tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:laptop-macbook-16" /></template>
