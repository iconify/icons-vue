<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tftf69b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tftf69b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bluetti" /></template>
