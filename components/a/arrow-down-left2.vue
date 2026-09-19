<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh4mmaclw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jh4mmaclw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-down-left2" /></template>
