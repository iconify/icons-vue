<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hswgs7b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hswgs7b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:jump-over-backwards-16" /></template>
