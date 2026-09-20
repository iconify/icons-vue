<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhmruf79x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhmruf79x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:facebook-solid" /></template>
