<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2yme1wsh.css';
import '../../css/w/wyg7xl8ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="z2yme1wsh"/><path class="wyg7xl8ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:college-11" /></template>
