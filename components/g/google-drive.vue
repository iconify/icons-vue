<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekeukp4zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ekeukp4zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:google-drive" /></template>
