<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bzvk8cecd.css';
import '../../css/s/s_3dx5bpj.css';
import '../../css/y/y467enbsf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBTXdndyG"><g class="ft5dv1b6b"><circle class="bzvk8cecd"/><circle transform="matrix(-1 0 0 1 24 24)" class="s_3dx5bpj"/><path class="y467enbsf"/></g></mask></defs><path mask="url(#SVGBTXdndyG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:auto-focus" /></template>
