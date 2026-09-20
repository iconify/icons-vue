<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlymt9bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hlymt9bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crosswalk-markings-lines" /></template>
