<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m79pj-b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m79pj-b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:airplay" /></template>
