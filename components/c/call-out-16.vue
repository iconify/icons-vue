<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftupilb-m.css';
import '../../css/l/lgcy8m5fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ftupilb-m"/><path class="lgcy8m5fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:call-out-16" /></template>
