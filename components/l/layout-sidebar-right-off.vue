<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj465u-3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bj465u-3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-sidebar-right-off" /></template>
