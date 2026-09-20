<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmy9rcb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmy9rcb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cart-check-solid" /></template>
