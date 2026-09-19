<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdba18qql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kdba18qql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:ballot-box-with-check-filled" /></template>
