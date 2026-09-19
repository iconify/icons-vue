<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brbyr1_7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="brbyr1_7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-surprise" /></template>
