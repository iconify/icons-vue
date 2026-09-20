<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j36ek5mfl.css';
import '../../css/w/wyq4150dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j36ek5mfl"/><path class="wyq4150dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cr-nmaster-dark" /></template>
