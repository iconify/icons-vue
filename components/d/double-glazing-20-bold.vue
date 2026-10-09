<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k86affo2a.css';
import '../../css/a/avn053b0m.css';
import '../../css/b/brp4g5bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k86affo2a"/><path class="avn053b0m"/><path class="brp4g5bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:double-glazing-20-bold" /></template>
