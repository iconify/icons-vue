<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tc51908st.css';
import '../../css/h/h07egnnok.css';
import '../../css/e/eld-26s5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="tc51908st"/><path class="h07egnnok"/><path clip-rule="evenodd" class="eld-26s5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:feed" /></template>
