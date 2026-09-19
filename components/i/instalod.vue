<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gllnf0blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gllnf0blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:instalod" /></template>
