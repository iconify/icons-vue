<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv2s_thge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kv2s_thge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crosswalk-markings-lines-paired" /></template>
