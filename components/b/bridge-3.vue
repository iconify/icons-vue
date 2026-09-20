<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq9zcrbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq9zcrbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bridge-3" /></template>
