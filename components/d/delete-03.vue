<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbdl0_bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbdl0_bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-03" /></template>
