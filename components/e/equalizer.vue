<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhwcmabhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="rhwcmabhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:equalizer" /></template>
