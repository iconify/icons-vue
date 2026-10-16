<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sffhwnb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":310,"height":310};
const content = `<path class="sffhwnb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cockpit-cms-dark" /></template>
