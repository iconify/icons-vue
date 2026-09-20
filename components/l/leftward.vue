<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo9pswbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oo9pswbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:leftward" /></template>
