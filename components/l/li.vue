<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/p/pq2i8kiiw.css';
import '../../css/x/xs5ohebgj.css';
import '../../css/w/wzs6oic2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="pq2i8kiiw"/><path class="xs5ohebgj"/><path class="wzs6oic2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:li" /></template>
