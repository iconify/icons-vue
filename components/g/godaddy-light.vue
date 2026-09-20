<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqqsz-bhg.css';
import '../../css/j/j_opgppca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":166,"height":34};
const content = `<path class="pqqsz-bhg prefix__path-mobile"/><path class="j_opgppca prefix__path-desktop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:godaddy-light" /></template>
