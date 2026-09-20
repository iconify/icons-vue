<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt6gxp18b.css';
import '../../css/u/u5p0aybko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wt6gxp18b"/><path class="u5p0aybko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:grails" /></template>
