<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs6rvfdlb.css';
import '../../css/e/ea83p6byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xs6rvfdlb"/><path class="ea83p6byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-pen-20" /></template>
