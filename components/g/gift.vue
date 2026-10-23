<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5j6zpkhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5j6zpkhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gift" /></template>
