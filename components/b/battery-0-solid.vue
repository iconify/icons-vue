<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5l_d69-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5l_d69-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:battery-0-solid" /></template>
