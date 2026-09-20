<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdbu7kk1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdbu7kk1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dialer-keypad-fill" /></template>
