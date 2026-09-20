<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj8nszb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj8nszb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:checkbox-checked-solid-expressive" /></template>
