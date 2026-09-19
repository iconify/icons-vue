<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w25h46bvy.css';
import '../../css/f/fuqf47bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w25h46bvy"/><path class="fuqf47bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flag-chequered-filled" /></template>
