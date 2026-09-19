<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hvb16ibtn.css';
import '../../css/j/j9lx0zklz.css';
import '../../css/e/erhl3ib4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hvb16ibtn"/><path class="j9lx0zklz"/><path class="erhl3ib4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cowboy-hat" /></template>
