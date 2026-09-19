<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzmcw3ump.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzmcw3ump"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:computer-ethernet" /></template>
