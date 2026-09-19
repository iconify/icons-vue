<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2_9zfvmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e2_9zfvmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:chevron-up-round" /></template>
