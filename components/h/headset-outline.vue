<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymicfbb2j.css';
import '../../css/r/rhba1dbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymicfbb2j"/><path class="rhba1dbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:headset-outline" /></template>
