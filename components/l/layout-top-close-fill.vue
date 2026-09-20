<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo9n361qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo9n361qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-top-close-fill" /></template>
