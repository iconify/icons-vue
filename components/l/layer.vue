<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smphz81xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smphz81xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:layer" /></template>
