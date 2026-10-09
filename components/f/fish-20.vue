<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3m6qu31q.css';
import '../../css/q/qe6mnv44d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b3m6qu31q"/><path class="qe6mnv44d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fish-20" /></template>
