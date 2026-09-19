<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf0wuc1-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wf0wuc1-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-right" /></template>
