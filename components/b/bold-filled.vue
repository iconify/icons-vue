<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/renmjyblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="renmjyblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bold-filled" /></template>
