<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du60o1kxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du60o1kxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chef-hat-line" /></template>
