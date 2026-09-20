<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9id3us9x.css';
import '../../css/g/gd_h2kbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9id3us9x"/><path class="gd_h2kbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:compose-24" /></template>
