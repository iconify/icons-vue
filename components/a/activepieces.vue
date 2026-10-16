<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb6hxoxix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":19};
const content = `<path class="nb6hxoxix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:activepieces" /></template>
