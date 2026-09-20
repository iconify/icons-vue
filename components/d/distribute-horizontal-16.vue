<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyu98sybs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xyu98sybs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:distribute-horizontal-16" /></template>
