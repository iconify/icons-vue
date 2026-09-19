<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq1nambya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rq1nambya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:four-leaf-clover" /></template>
