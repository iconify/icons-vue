<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_71-fb8o.css';
import '../../css/g/gg06_sb0j.css';
import '../../css/u/ut5psuaky.css';
import '../../css/p/pz2zo8bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_71-fb8o"/><path class="gg06_sb0j"/><path class="ut5psuaky"/><path class="pz2zo8bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:coin-stack" /></template>
