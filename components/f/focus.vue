<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kucvonbff.css';
import '../../css/w/w0_7cab0w.css';
import '../../css/s/s_3dx5bpj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhUb5Xdyy"><g class="ft5dv1b6b"><path class="kucvonbff"/><rect class="w0_7cab0w"/><circle transform="matrix(-1 0 0 1 24 24)" class="s_3dx5bpj"/></g></mask></defs><path mask="url(#SVGhUb5Xdyy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:focus" /></template>
