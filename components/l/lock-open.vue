<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaicczq3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vaicczq3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:lock-open" /></template>
