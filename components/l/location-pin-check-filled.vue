<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgqtkp22k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgqtkp22k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:location-pin-check-filled" /></template>
