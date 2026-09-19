<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzy6kp86h.css';
import '../../css/k/k70t2o__t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzy6kp86h"/><path class="k70t2o__t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fan" /></template>
