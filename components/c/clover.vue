<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjig8pqzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjig8pqzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:clover" /></template>
