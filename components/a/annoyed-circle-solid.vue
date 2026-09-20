<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7szmbwkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7szmbwkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:annoyed-circle-solid" /></template>
