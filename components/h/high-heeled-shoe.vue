<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms0e8vi6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ms0e8vi6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:high-heeled-shoe" /></template>
