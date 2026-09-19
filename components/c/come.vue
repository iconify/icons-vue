<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-_ohbfa.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwvM9ld2t"><path class="zw-_ohbfa"/></mask></defs><path mask="url(#SVGwvM9ld2t)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:come" /></template>
