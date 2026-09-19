<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp-z0dg_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xp-z0dg_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:archivebox-fill" /></template>
