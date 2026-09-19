<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtlbrsb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtlbrsb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:dental-chair-filled" /></template>
