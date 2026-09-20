<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3obo9bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3obo9bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:add-user-filled" /></template>
