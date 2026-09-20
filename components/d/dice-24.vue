<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2rq36bvg.css';
import '../../css/m/mzvqb-b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2rq36bvg"/><path class="mzvqb-b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dice-24" /></template>
