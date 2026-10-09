<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anpy_cbsi.css';
import '../../css/l/ljm5ww87o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="anpy_cbsi"/><path class="ljm5ww87o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:graduation-cap-20-bold" /></template>
