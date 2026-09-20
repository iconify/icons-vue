<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/n47rxdneh.css';
import '../../css/s/s6ae1bchi.css';
import '../../css/h/hbg0kobxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n47rxdneh"/><path class="s6ae1bchi"/><path class="hbg0kobxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cpu-charge" /></template>
