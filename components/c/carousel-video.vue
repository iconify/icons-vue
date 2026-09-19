<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/u/ul-q5sihi.css';
import '../../css/b/b0xh22bik.css';
import '../../css/e/efp14rd8v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn2kvzcwJ"><g class="wwvp95byt"><path class="ul-q5sihi"/><path class="b0xh22bik"/><path class="efp14rd8v"/></g></mask></defs><path mask="url(#SVGn2kvzcwJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:carousel-video" /></template>
