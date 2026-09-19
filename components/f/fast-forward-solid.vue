<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_1mesb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_1mesb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:fast-forward-solid" /></template>
