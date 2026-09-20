<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox8cu4u3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ox8cu4u3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clockwise-outline" /></template>
