<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npjel3gno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npjel3gno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevron-down" /></template>
