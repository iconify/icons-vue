<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drtdhtb_j.css';
import '../../css/c/cqbmk1byz.css';
import '../../css/p/p5ypd6bpk.css';
import '../../css/q/qlqnfnb8d.css';
import '../../css/h/hxyfhfb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="drtdhtb_j"/><path class="cqbmk1byz"/><path class="p5ypd6bpk"/><path class="qlqnfnb8d"/><path class="hxyfhfb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:fastlane" /></template>
