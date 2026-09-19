<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5i7ibc6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w5i7ibc6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:heart-slash-circle-fill" /></template>
