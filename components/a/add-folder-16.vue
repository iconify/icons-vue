<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrclfebok.css';
import '../../css/j/jheuc51zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wrclfebok"/><path class="jheuc51zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:add-folder-16" /></template>
