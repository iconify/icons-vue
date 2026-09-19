<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awwatjbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="awwatjbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:delicious" /></template>
