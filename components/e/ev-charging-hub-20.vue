<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr-gbkbpm.css';
import '../../css/l/l3f3ah6-k.css';
import '../../css/f/fd0qhnbkz.css';
import '../../css/y/y5yierbhk.css';
import '../../css/e/e8pcimbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mr-gbkbpm"/><path class="l3f3ah6-k"/><path class="fd0qhnbkz"/><path class="y5yierbhk"/><path class="e8pcimbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charging-hub-20" /></template>
