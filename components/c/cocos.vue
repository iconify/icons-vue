<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iixyqdzth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iixyqdzth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cocos" /></template>
