<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfawppb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mfawppb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:floppy-disk" /></template>
