<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urt6ydwht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="urt6ydwht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:envelope-open-fill" /></template>
