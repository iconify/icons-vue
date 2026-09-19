<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc0qlpbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="mc0qlpbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-fragment" /></template>
