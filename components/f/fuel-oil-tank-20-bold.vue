<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxs-cj0rl.css';
import '../../css/z/z9yfx3tkk.css';
import '../../css/u/uqtatsbzn.css';
import '../../css/q/qfs7nya9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bxs-cj0rl"/><path class="z9yfx3tkk"/><path class="uqtatsbzn"/><path class="qfs7nya9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-oil-tank-20-bold" /></template>
