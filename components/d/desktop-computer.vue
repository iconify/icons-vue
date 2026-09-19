<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzf2h5bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzf2h5bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desktop-computer" /></template>
