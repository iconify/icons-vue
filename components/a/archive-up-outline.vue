<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzzw40e_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzzw40e_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-up-outline" /></template>
