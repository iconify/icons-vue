<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0jvsm82e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q0jvsm82e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:in-ear-headphones-solid" /></template>
