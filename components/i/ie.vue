<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_5iorr6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a_5iorr6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:ie" /></template>
