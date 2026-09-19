<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk7i4qv0w.css';
import '../../css/b/bu5x6-ooy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lk7i4qv0w"/><path class="bu5x6-ooy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:book" /></template>
