<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sztn4yorr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sztn4yorr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:laptop" /></template>
