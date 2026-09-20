<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8nitrb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8nitrb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:figshare" /></template>
