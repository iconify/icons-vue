<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by22ydp5s.css';
import '../../css/j/j7a0fv5du.css';
import '../../css/e/el9y-0crz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by22ydp5s"/><path class="j7a0fv5du"/><path class="el9y-0crz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-tree-bold" /></template>
