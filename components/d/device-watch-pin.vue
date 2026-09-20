<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq6zqpbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq6zqpbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-pin" /></template>
