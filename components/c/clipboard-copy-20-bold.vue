<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6t120hgc.css';
import '../../css/b/b-cut7-tv.css';
import '../../css/i/iqqj1-bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z6t120hgc"/><path class="b-cut7-tv"/><path class="iqqj1-bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-copy-20-bold" /></template>
