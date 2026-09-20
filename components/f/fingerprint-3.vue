<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7gpvrbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7gpvrbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fingerprint-3" /></template>
