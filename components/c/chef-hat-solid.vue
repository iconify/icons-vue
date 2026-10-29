<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvz2wcf8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvz2wcf8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chef-hat-solid" /></template>
