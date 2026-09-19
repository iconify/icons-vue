<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mki0tacaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="mki0tacaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hotdog" /></template>
