<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9-u7do2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j9-u7do2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-font-filled" /></template>
