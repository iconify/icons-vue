<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqeqdemwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rqeqdemwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:envelope" /></template>
