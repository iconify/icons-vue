<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo3c7mblw.css';
import '../../css/i/idhyedbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fo3c7mblw"/><path class="idhyedbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:log-out-16" /></template>
