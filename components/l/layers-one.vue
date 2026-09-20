<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bey4ik7pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bey4ik7pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layers-one" /></template>
