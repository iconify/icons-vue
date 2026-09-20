<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt7xtbczv.css';
import '../../css/f/fqgt3213z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt7xtbczv"/><path class="fqgt3213z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:5dive" /></template>
