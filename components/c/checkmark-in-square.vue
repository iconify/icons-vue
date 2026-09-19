<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnj-uwb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cnj-uwb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:checkmark-in-square" /></template>
