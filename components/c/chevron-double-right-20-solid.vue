<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omg2h_xnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="omg2h_xnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-right-20-solid" /></template>
