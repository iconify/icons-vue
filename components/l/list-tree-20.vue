<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acadc4zqf.css';
import '../../css/k/k9wblp0cn.css';
import '../../css/p/p4jr7vbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="acadc4zqf"/><path class="k9wblp0cn"/><path class="p4jr7vbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-tree-20" /></template>
