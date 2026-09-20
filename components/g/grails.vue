<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bji6subwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bji6subwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:grails" /></template>
