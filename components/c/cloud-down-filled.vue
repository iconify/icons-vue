<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oenbs8bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oenbs8bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-down-filled" /></template>
