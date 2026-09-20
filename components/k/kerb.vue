<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdd7-wone.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qdd7-wone"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:kerb" /></template>
