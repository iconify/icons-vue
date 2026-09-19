<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylgliubwh.css';
import '../../css/w/w-gbphaza.css';
import '../../css/v/vlmlzenit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ylgliubwh"/><path class="w-gbphaza"/><path class="vlmlzenit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:dash" /></template>
