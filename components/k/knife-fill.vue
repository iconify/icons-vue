<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue5b__b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue5b__b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:knife-fill" /></template>
