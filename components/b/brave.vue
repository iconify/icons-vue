<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayspz-bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ayspz-bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:brave" /></template>
