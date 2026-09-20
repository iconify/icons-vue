<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq32u3btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq32u3btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:acode" /></template>
