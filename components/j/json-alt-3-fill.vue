<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2t895bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2t895bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:json-alt-3-fill" /></template>
