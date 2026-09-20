<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyi0tcctg.css';
import '../../css/b/bz41hmbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="fyi0tcctg"/><path class="bz41hmbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-drinking-fountain" /></template>
