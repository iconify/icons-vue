<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bof_92yus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bof_92yus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-diamond-solid" /></template>
