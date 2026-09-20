<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weccofbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weccofbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-minus" /></template>
