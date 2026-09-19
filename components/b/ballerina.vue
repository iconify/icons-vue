<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfc3gybyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":283,"height":512};
const content = `<path class="qfc3gybyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ballerina" /></template>
