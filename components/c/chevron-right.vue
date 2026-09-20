<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v31zzfo0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":16};
const content = `<path class="v31zzfo0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-right" /></template>
