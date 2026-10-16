<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dom_6oycu.css';
import '../../css/k/k5lxwxbxz.css';
import '../../css/h/h284w7bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dom_6oycu"/><path class="k5lxwxbxz"/><path class="h284w7bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cam-20" /></template>
