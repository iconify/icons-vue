<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff6usbbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ff6usbbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:creditcard-fill" /></template>
