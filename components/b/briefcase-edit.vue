<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txvyk-sgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txvyk-sgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-edit" /></template>
