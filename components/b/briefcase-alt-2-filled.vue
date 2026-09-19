<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vamcxub9f.css';
import '../../css/i/i7a-gbc6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vamcxub9f"/><path class="i7a-gbc6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:briefcase-alt-2-filled" /></template>
