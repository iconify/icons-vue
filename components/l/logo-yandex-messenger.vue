<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj_tu-bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vj_tu-bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-yandex-messenger" /></template>
