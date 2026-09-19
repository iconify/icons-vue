<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f-rc7hbej.css';
import '../../css/m/mal9x4b_u.css';
import '../../css/v/vjupb11qn.css';
import '../../css/a/a30pbeb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f-rc7hbej"/><path class="mal9x4b_u"/><path class="vjupb11qn"/><path class="a30pbeb1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:image-outline" /></template>
