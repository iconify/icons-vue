<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gft6yrvkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gft6yrvkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:aral" /></template>
