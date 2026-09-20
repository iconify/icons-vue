<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lg3oiabbn.css';
import '../../css/l/l41a-6b0f.css';
import '../../css/m/mow9f5btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":55,"height":50};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lg3oiabbn"/><path class="l41a-6b0f"/><path class="mow9f5btu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cody" /></template>
