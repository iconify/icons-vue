<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhsrgzbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhsrgzbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:deploy" /></template>
