<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-mgshf6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q-mgshf6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:keyboard" /></template>
