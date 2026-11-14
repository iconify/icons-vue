<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ismf5ilwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ismf5ilwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:current-dc" /></template>
