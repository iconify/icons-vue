<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjcq7db9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjcq7db9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-spark" /></template>
