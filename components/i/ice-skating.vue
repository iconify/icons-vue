<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecnugpbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ecnugpbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:ice-skating" /></template>
