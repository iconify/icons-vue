<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftt71gbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ftt71gbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bandage" /></template>
