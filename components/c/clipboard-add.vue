<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njvz10t4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="njvz10t4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard-add" /></template>
