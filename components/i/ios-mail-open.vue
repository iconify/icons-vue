<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znuap0b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="znuap0b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-mail-open" /></template>
