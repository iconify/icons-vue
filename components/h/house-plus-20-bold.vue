<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuveebb1b.css';
import '../../css/z/ziroa4b5h.css';
import '../../css/t/t51h00xtk.css';
import '../../css/p/prfptqbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zuveebb1b"/><path class="ziroa4b5h"/><path class="t51h00xtk"/><path class="prfptqbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-plus-20-bold" /></template>
