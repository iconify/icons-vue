<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu2fvcb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vu2fvcb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:code-small" /></template>
