<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqlot2byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqlot2byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-open-outline" /></template>
