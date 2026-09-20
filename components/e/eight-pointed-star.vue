<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l11z416ub.css';
import '../../css/t/twzfc7dpg.css';
import '../../css/k/k287uf_wt.css';
import '../../css/i/iwjrb3bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="l11z416ub"/><path class="twzfc7dpg"/><path class="k287uf_wt"/><path class="iwjrb3bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:eight-pointed-star" /></template>
