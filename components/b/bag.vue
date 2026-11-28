<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlamo1ykq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlamo1ykq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bag" /></template>
