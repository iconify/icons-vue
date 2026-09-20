<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmjy-5bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qmjy-5bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:drums" /></template>
