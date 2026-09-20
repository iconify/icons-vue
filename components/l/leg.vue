<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdn-dqb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gdn-dqb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:leg" /></template>
