<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw2gtd80r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw2gtd80r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bucket-filled" /></template>
