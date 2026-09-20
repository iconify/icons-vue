<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wivg6zlgt.css';
import '../../css/g/gh_fdcczq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wivg6zlgt"/><path class="gh_fdcczq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-check" /></template>
