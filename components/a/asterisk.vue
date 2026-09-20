<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i62i6jc8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i62i6jc8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:asterisk" /></template>
