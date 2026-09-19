<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r50tbhkmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r50tbhkmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-musical-notes" /></template>
