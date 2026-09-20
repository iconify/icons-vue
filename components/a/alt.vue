<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb_g5bbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lb_g5bbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:alt" /></template>
