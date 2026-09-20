<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu3p-s68u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu3p-s68u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-exit-sharp-fill" /></template>
