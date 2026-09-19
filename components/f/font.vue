<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow9tyrz_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":925,"height":1000};
const content = `<path class="ow9tyrz_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:font" /></template>
