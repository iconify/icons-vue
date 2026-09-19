<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d47xi2b9o.css';
import '../../css/f/fjryjwbdx.css';
import '../../css/n/nydaq4aap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="fjryjwbdx"/><path class="nydaq4aap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:krona" /></template>
