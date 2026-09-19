<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlee1f3sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1280};
const content = `<path class="mlee1f3sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:eye" /></template>
