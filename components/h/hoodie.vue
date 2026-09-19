<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dvkq3fkcy.css';
import '../../css/g/gzpm6zbzn.css';
import '../../css/j/jqnus1b-u.css';
import '../../css/b/brwm01bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dvkq3fkcy"/><path class="gzpm6zbzn"/><path class="jqnus1b-u"/><path class="brwm01bnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hoodie" /></template>
