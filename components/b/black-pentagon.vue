<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krg4aibpx.css';
import '../../css/z/z68qmysoe.css';
import '../../css/s/s3_8gac3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="krg4aibpx"/><path class="z68qmysoe"/><path class="s3_8gac3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-pentagon" /></template>
