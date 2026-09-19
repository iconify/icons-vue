<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jox__zbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jox__zbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:desktop-device" /></template>
