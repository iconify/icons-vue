<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwe291bsk.css';
import '../../css/m/mgz4g1bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mwe291bsk"/><path class="mgz4g1bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:eye-minus" /></template>
