<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uibuzzbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uibuzzbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:computer-across-filled" /></template>
