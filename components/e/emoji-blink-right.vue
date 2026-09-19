<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hau3ssbei.css';
import '../../css/b/b4wekebzy.css';
import '../../css/k/kja35acnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hau3ssbei"/><path class="b4wekebzy"/><path class="kja35acnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:emoji-blink-right" /></template>
