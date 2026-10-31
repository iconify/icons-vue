<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-ahyi0ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u-ahyi0ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-open-gabled-building" /></template>
