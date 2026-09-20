<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng-7dbvkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ng-7dbvkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:back-square-outline" /></template>
