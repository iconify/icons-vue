<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/f4-hall_c.css';
import '../../css/a/a2yusv--h.css';
import '../../css/e/exydi1bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="f4-hall_c"/><path class="a2yusv--h"/><path class="exydi1bdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:eye" /></template>
