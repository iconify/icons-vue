<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oquswcb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oquswcb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:crate" /></template>
