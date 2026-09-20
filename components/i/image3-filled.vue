<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv6o-j_2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv6o-j_2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image3-filled" /></template>
