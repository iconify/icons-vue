<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/b/brmn1ccqk.css';
import '../../css/n/nft682v4h.css';
import '../../css/k/kbe5kybxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGuywqVbel"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGuywqVbel)"><path class="brmn1ccqk"/><path class="nft682v4h"/><path class="kbe5kybxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:lang-non" /></template>
