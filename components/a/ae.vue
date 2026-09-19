<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/n/n7gshya7f.css';
import '../../css/a/afa1hhk4p.css';
import '../../css/c/czp1efbvf.css';
import '../../css/c/c2_knxbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="n7gshya7f"/><path class="afa1hhk4p"/><path class="czp1efbvf"/><path class="c2_knxbzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:ae" /></template>
