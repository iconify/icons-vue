<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lip-g3b5r.css';
import '../../css/b/brh819bvq.css';
import '../../css/l/lyd-dmbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="lip-g3b5r"/><path class="brh819bvq"/><path class="lyd-dmbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-todo" /></template>
