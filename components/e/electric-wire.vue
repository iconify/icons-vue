<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aftsqzznu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aftsqzznu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:electric-wire" /></template>
