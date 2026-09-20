<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfh5m5bzm.css';
import '../../css/k/kwvibbeog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bfh5m5bzm"/><path clip-rule="evenodd" class="kwvibbeog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:location-16" /></template>
