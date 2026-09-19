<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tzg6v5btu.css';
import '../../css/b/b2zbrybhm.css';
import '../../css/n/n5intik2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tzg6v5btu"/><path class="b2zbrybhm"/><path class="n5intik2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:adventure" /></template>
