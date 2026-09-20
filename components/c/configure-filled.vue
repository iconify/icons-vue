<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_rygdchc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t_rygdchc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:configure-filled" /></template>
