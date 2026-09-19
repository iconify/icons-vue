<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj6el_b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj6el_b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:checkmark-circled" /></template>
