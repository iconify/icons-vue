<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue99ppw5a.css';
import '../../css/s/sach5mb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ue99ppw5a"/><path class="sach5mb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:left-right-black-arrow" /></template>
