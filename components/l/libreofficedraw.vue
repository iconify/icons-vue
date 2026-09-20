<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuktlbv5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuktlbv5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:libreofficedraw" /></template>
