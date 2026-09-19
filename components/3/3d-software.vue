<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqf62mbvw.css';
import '../../css/r/rmzj1bb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hqf62mbvw"/><path class="rmzj1bb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:3d-software" /></template>
