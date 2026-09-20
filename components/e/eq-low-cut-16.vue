<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs6jyqhex.css';
import '../../css/f/f6s9xdlma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gs6jyqhex"/><path class="f6s9xdlma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eq-low-cut-16" /></template>
