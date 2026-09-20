<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktonl8bjx.css';
import '../../css/h/h8ocnybfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktonl8bjx"/><path class="h8ocnybfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:after-effects" /></template>
