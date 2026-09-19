<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itc5zdbai.css';
import '../../css/v/vffo02v_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itc5zdbai"/><path class="vffo02v_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-minus-outline" /></template>
