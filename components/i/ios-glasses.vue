<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwm7qldww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xwm7qldww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-glasses" /></template>
