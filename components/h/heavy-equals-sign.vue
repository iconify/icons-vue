<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha_ce1bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ha_ce1bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:heavy-equals-sign" /></template>
