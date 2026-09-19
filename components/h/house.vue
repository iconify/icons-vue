<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hysorxn0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hysorxn0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:house" /></template>
