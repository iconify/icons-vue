<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urh7yqbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urh7yqbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dumbbell-filled" /></template>
