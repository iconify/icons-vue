<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r2iitdbys.css';
import '../../css/t/tkiz4rbld.css';
import '../../css/s/s2j1gkbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="r2iitdbys"/><path class="tkiz4rbld"/><path class="s2j1gkbik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:arrow-down-right" /></template>
