<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fih1jvc2u.css';
import '../../css/l/lgevicgqz.css';
import '../../css/y/ysv--kbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fih1jvc2u"/><path class="lgevicgqz"/><path class="ysv--kbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:automation" /></template>
