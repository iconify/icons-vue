<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txh5gkfyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txh5gkfyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gumroad-fill" /></template>
