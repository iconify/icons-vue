<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5i58z2mb.css';
import '../../css/m/mi4i07bgh.css';
import '../../css/j/jat07cb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d5i58z2mb"/><path class="mi4i07bgh"/><path class="jat07cb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:elderly-20" /></template>
