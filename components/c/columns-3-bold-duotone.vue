<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2-x-cbeh.css';
import '../../css/q/qykqcq_5w.css';
import '../../css/g/gyjvu3nrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-x-cbeh"/><path class="qykqcq_5w"/><path class="gyjvu3nrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-bold-duotone" /></template>
