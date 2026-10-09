<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9umykbju.css';
import '../../css/e/esmbl8oyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s9umykbju"/><path class="esmbl8oyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-left-20-bold" /></template>
