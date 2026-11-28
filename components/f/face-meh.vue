<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxh1tmbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxh1tmbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:face-meh" /></template>
