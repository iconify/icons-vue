<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwxaeqbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cwxaeqbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:controller-volume" /></template>
