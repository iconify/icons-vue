<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/r/rb-j961er.css';
import '../../css/n/n0-b_oysz.css';
import '../../css/l/ljtm_oblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="rb-j961er"/><path class="n0-b_oysz"/><path class="ljtm_oblt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:feed-burner-logo" /></template>
