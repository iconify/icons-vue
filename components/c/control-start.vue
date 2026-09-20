<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-el6m66m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l-el6m66m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:control-start" /></template>
