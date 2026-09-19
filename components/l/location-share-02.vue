<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c3buayb6b.css';
import '../../css/i/im7es_bhr.css';
import '../../css/l/lbpdwbb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c3buayb6b"/><path class="im7es_bhr"/><path class="lbpdwbb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:location-share-02" /></template>
