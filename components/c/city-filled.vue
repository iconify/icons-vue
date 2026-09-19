<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s89b7sskt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s89b7sskt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:city-filled" /></template>
