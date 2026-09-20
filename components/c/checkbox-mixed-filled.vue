<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjicw-buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mjicw-buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:checkbox-mixed-filled" /></template>
