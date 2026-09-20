<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj6j6-bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj6j6-bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-off-sharp" /></template>
