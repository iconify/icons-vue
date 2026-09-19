<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui2tq9n4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ui2tq9n4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:clothes-pants-short" /></template>
