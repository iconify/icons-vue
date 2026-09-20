<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/pwiyovb5b.css';
import '../../css/b/bbicxkb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect transform="matrix(1 0 0 -1 3.75 20.25)" class="pwiyovb5b"/><path class="bbicxkb-t"/><rect transform="matrix(1 0 0 -1 3.75 10.25)" class="pwiyovb5b"/><rect transform="matrix(1 0 0 -1 13.75 10.25)" class="pwiyovb5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:app-remove" /></template>
