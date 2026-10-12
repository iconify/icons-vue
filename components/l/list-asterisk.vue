<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-1ng1bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-1ng1bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:list-asterisk" /></template>
