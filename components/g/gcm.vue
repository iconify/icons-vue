<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2bgyq9rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2bgyq9rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:gcm" /></template>
