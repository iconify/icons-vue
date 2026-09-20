<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awf25-t-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="awf25-t-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:edit-outline" /></template>
