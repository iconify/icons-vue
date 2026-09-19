<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1_u81bnd.css';
import '../../css/u/u8hb6sbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b s1_u81bnd"/><path class="b u8hb6sbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bowl-bubbles-filled" /></template>
