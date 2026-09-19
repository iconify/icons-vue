<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyij-mfno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyij-mfno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:function" /></template>
