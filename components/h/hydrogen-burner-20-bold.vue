<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyiqdq-1y.css';
import '../../css/e/ek3-3_91h.css';
import '../../css/f/fpc4qk6ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jyiqdq-1y"/><path class="ek3-3_91h"/><path class="fpc4qk6ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-burner-20-bold" /></template>
