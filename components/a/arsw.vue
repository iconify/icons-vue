<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjiisjjws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjiisjjws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:arsw" /></template>
