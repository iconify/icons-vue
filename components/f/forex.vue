<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olzavh4ia.css';
import '../../css/w/wqvb8lb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olzavh4ia"/><path clip-rule="evenodd" class="wqvb8lb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:forex" /></template>
