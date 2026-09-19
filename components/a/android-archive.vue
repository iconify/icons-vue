<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9a2cqbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h9a2cqbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-archive" /></template>
