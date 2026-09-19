<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpypgjb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpypgjb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:egg-outline" /></template>
