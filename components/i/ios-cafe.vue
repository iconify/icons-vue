<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi8qeub9j.css';
import '../../css/g/gzw_lcbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bi8qeub9j"/><path class="gzw_lcbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cafe" /></template>
