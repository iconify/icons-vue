<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj5q7kbzd.css';
import '../../css/n/nabjh0sde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj5q7kbzd"/><path class="nabjh0sde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:eye-off-sharp" /></template>
