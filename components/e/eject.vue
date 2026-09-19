<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi6ucj14t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qi6ucj14t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:eject" /></template>
