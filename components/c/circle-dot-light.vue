<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1k_fi90e.css';
import '../../css/l/ly7yqvbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1k_fi90e"/><path class="ly7yqvbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:circle-dot-light" /></template>
