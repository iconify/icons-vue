<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd5ux5bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hd5ux5bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-return-small-filled" /></template>
