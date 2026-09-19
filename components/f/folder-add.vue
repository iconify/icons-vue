<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz6zcpb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz6zcpb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:folder-add" /></template>
