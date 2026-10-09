<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rekkswb7u.css';
import '../../css/f/f1fwzpb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rekkswb7u"/><path class="f1fwzpb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:credit-card-20" /></template>
