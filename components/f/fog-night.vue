<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r43rvnpow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r43rvnpow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fog-night" /></template>
