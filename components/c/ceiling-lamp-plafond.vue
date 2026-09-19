<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwwq52lah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwwq52lah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-lamp-plafond" /></template>
