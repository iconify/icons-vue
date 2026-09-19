<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/c/cbim_vtrq.css';
import '../../css/y/ytiz7kbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsIg0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsIg0)"><path class="cbim_vtrq"/><path class="ytiz7kbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:ig" /></template>
