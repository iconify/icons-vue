<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7q-yqbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7q-yqbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:call-add-filled" /></template>
