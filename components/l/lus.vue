<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/q/qw1f0bfkg.css';
import '../../css/o/ou1b4gbff.css';
import '../../css/b/br4dn_b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsLus0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsLus0)"><path class="qw1f0bfkg"/><path class="ou1b4gbff"/><circle class="br4dn_b2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:lus" /></template>
