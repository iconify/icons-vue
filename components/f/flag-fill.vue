<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu-vi5btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu-vi5btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:flag-fill" /></template>
