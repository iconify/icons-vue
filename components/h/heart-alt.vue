<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4ygkcb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="s4ygkcb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:heart-alt" /></template>
