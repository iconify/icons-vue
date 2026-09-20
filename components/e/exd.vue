<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t253e1abv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t253e1abv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:exd" /></template>
