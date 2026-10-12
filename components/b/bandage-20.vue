<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwzn8jb7l.css';
import '../../css/x/xhaqngbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bwzn8jb7l"/><path class="xhaqngbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bandage-20" /></template>
