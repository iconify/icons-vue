<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iami2m70c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="iami2m70c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-download-fill" /></template>
