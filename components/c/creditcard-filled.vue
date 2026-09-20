<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbl6cbcom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbl6cbcom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:creditcard-filled" /></template>
