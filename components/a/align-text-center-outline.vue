<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8p4bpbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n8p4bpbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-text-center-outline" /></template>
