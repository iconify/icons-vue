<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjlkkr6dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjlkkr6dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:google-drive" /></template>
