<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uk1uhtb2n.css';
import '../../css/u/uf6sm2mwe.css';
import '../../css/w/wsazxob3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uk1uhtb2n"/><path class="uf6sm2mwe"/><path class="wsazxob3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-remove-01" /></template>
