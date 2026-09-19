<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th5u_7n9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="th5u_7n9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:google-hangouts" /></template>
