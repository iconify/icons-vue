<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkt0su85n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gkt0su85n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:info-circle-fill" /></template>
