<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_o-pw-1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_o-pw-1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:caret-back-circle" /></template>
