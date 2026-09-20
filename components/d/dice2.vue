<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofpqxnb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ofpqxnb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dice2" /></template>
