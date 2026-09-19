<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owv2r90mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="owv2r90mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:canadian-maple-leaf" /></template>
