<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqbp4ccby.css';
import '../../css/f/fos7arooz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dqbp4ccby"/><path class="fos7arooz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:anchor-bottom-right-16" /></template>
