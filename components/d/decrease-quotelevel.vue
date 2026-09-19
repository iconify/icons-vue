<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx80h9bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rx80h9bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:decrease-quotelevel" /></template>
