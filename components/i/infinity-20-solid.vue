<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z726f_ufb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z726f_ufb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:infinity-20-solid" /></template>
