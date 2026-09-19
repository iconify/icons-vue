<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiyviqlny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiyviqlny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:google-play-solid" /></template>
