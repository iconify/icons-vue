<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgjx29b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zgjx29b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:kerb-rolled" /></template>
