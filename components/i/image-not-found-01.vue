<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zj-kox43j.css';
import '../../css/h/hew_hqbtw.css';
import '../../css/f/frzp0kb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zj-kox43j"/><path class="hew_hqbtw"/><path class="frzp0kb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-not-found-01" /></template>
