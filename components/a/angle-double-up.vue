<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo4avb77y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1280};
const content = `<path class="bo4avb77y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:angle-double-up" /></template>
