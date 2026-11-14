<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwdjqwbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwdjqwbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-ringing-03" /></template>
