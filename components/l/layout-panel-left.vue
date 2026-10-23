<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usjwfgovv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usjwfgovv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-panel-left" /></template>
