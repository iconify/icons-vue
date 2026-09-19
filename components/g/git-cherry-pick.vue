<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c-m63qg-e.css';
import '../../css/p/pe7zzcn4c.css';
import '../../css/e/e6b6ro_mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="c-m63qg-e"/><path class="pe7zzcn4c"/><path class="e6b6ro_mc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:git-cherry-pick" /></template>
