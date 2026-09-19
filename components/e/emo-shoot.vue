<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo56wubgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1948,"height":1000};
const content = `<path class="lo56wubgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-shoot" /></template>
