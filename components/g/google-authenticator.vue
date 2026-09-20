<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os-wwac5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os-wwac5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-authenticator" /></template>
