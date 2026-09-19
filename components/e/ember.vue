<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taf3qob0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taf3qob0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ember" /></template>
