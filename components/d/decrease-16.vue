<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azvkn8bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="azvkn8bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:decrease-16" /></template>
