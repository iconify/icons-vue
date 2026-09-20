<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjksq2bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjksq2bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-child-outline" /></template>
