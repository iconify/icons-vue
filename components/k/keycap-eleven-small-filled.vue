<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-ry7yewp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m-ry7yewp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-eleven-small-filled" /></template>
