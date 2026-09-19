<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-thqdb7y.css';
import '../../css/w/w-335_d0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-thqdb7y"/><path class="w-335_d0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:camera" /></template>
