<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn5rlrsrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn5rlrsrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-3" /></template>
