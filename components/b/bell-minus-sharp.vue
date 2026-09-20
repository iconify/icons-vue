<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds5e4p7zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds5e4p7zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-minus-sharp" /></template>
