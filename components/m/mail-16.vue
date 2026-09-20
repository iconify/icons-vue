<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v96p-_b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v96p-_b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mail-16" /></template>
