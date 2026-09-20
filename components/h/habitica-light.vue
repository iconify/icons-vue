<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtqwdrb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jtqwdrb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:habitica-light" /></template>
