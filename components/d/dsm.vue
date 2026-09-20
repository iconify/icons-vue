<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7nujkzvg.css';
import '../../css/u/u9y3aibok.css';
import '../../css/v/vf6i915qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7nujkzvg"/><path class="u9y3aibok"/><path class="vf6i915qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dsm" /></template>
