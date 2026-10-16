<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b24n32b6u.css';
import '../../css/j/jdj652_du.css';
import '../../css/m/m-d02bb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b24n32b6u"/><path class="jdj652_du"/><path class="m-d02bb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-tree-20-bold" /></template>
