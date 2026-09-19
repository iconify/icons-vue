<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm6pyibmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fm6pyibmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:headset" /></template>
