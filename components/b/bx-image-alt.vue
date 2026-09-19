<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c98at3bul.css';
import '../../css/i/ii_7x9egm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c98at3bul"/><path class="ii_7x9egm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-image-alt" /></template>
