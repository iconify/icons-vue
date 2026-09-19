<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4jd8gbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p4jd8gbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:hook" /></template>
