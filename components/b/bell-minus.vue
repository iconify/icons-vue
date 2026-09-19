<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv7o6gbgs.css';
import '../../css/a/a9nhzacts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv7o6gbgs"/><path class="a9nhzacts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bell-minus" /></template>
