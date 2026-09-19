<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgbmqc20c.css';
import '../../css/r/r-v6gebze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgbmqc20c"/><path class="r-v6gebze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:location-pin-filled" /></template>
