<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-e56suxy.css';
import '../../css/g/gjx1o8bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g-e56suxy"/><path clip-rule="evenodd" class="gjx1o8bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:file-no-access-solid" /></template>
