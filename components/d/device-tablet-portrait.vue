<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rghi9ibtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rghi9ibtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:device-tablet-portrait" /></template>
