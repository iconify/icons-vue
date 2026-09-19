<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaxi56bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gaxi56bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlepencil" /></template>
