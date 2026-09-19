<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox61td1yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ox61td1yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-down2" /></template>
