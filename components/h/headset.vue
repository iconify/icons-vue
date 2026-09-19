<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec4-tcc7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ec4-tcc7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:headset" /></template>
