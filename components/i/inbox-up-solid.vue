<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx930cc8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx930cc8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:inbox-up-solid" /></template>
