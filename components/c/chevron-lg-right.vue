<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_0hc807b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t_0hc807b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:chevron-lg-right" /></template>
