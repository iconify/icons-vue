<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcx275bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcx275bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-circle-solid" /></template>
