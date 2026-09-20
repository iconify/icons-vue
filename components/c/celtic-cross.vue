<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucdh_db4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ucdh_db4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:celtic-cross" /></template>
