<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqhmgi-ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqhmgi-ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:info-circle-filled" /></template>
