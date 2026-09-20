<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3zjk--8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w3zjk--8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dice-3-solid" /></template>
