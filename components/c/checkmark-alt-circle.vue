<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crld5ikee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="crld5ikee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-alt-circle" /></template>
