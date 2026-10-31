<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qinyeubxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qinyeubxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-checked-round" /></template>
