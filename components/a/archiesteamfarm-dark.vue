<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm6ivxbpv.css';
import '../../css/r/ryv1mabbs.css';
import '../../css/i/igam31bgk.css';
import '../../css/t/tk1cyqr2k.css';
import '../../css/g/gw9hi4k1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sm6ivxbpv"/><path class="ryv1mabbs"/><path class="igam31bgk"/><path class="tk1cyqr2k"/><path class="gw9hi4k1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:archiesteamfarm-dark" /></template>
