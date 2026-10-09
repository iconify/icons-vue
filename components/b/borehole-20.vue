<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkmn36bzs.css';
import '../../css/v/vwsuc6gog.css';
import '../../css/u/u3r8q7x0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zkmn36bzs"/><path class="vwsuc6gog"/><path class="u3r8q7x0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:borehole-20" /></template>
