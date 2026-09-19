<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itc5zdbai.css';
import '../../css/s/s7lyd-ozi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itc5zdbai"/><path class="s7lyd-ozi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-clock-outline" /></template>
