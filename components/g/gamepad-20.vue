<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm0hlun-r.css';
import '../../css/b/bfq0kbdtf.css';
import '../../css/c/c_swoacmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tm0hlun-r"/><path class="bfq0kbdtf"/><path class="c_swoacmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gamepad-20" /></template>
