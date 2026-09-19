<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4r_6ibkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v4r_6ibkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:dog" /></template>
