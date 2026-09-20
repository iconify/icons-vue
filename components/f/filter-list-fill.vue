<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2vr2vnyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2vr2vnyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:filter-list-fill" /></template>
