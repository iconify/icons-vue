<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m843eubsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m843eubsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:corner-up-left" /></template>
