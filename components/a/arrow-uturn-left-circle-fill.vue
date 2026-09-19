<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsf6grz5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lsf6grz5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-left-circle-fill" /></template>
