<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rijrl-bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rijrl-bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:door-sharp" /></template>
