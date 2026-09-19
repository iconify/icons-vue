<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/t/thr1nx8vi.css';
import '../../css/b/b5_d2kbgp.css';
import '../../css/m/mc4217btw.css';
import '../../css/b/bffubcecu.css';
import '../../css/k/kzqdr-bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="thr1nx8vi"/><path class="b5_d2kbgp"/><path class="mc4217btw"/><path class="bffubcecu"/><path class="kzqdr-bzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:eh" /></template>
