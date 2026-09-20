<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmjc3fw5x.css';
import '../../css/d/d3p561beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hmjc3fw5x"/><path class="d3p561beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:convoy-dark" /></template>
