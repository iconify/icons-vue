<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmx89-dah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmx89-dah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:female" /></template>
