<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/n/nnfv0rblz.css';
import '../../css/i/iw7_91opa.css';
import '../../css/p/pfurf2bom.css';
import '../../css/r/ryb_ukbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGuywqVbel"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGuywqVbel)"><path class="nnfv0rblz"/><path class="iw7_91opa"/><path class="pfurf2bom"/><path class="ryb_ukbgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:cp" /></template>
