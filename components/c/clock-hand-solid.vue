<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjfjeoy3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjfjeoy3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-hand-solid" /></template>
