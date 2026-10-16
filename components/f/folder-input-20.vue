<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykwqglbwb.css';
import '../../css/p/p18co30jw.css';
import '../../css/c/cglx9k6ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ykwqglbwb"/><path class="p18co30jw"/><path class="cglx9k6ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-input-20" /></template>
