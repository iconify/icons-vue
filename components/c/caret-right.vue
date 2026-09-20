<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldhud7ziz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldhud7ziz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:caret-right" /></template>
