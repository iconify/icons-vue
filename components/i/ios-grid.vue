<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj9htxb2j.css';
import '../../css/q/qjl0smrdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fj9htxb2j"/><path class="qjl0smrdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-grid" /></template>
