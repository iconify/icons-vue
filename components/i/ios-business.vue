<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3_381bly.css';
import '../../css/i/iz88rmbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3_381bly"/><path class="iz88rmbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-business" /></template>
