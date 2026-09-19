<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpd2i7b0i.css';
import '../../css/t/th-zvacct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vpd2i7b0i"/><path class="th-zvacct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hashicorp" /></template>
