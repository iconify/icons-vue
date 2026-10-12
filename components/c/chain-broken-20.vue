<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd_z49b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jd_z49b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chain-broken-20" /></template>
