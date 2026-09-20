<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c20pa821i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c20pa821i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:gold-flat" /></template>
