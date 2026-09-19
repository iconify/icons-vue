<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f66bep6ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f66bep6ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-flushed" /></template>
