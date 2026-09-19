<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot3ue-bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":512};
const content = `<path class="ot3ue-bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cubit" /></template>
