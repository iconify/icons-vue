<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psp8mbbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psp8mbbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:emotion-laugh-line" /></template>
