<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c06y5ub8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c06y5ub8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-meh-20-solid" /></template>
