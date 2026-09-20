<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypy0npbna.css';
import '../../css/g/g0uat02ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ypy0npbna"/><path class="g0uat02ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:karatelabs" /></template>
