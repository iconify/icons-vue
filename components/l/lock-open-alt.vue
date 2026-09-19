<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km61y45mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km61y45mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lock-open-alt" /></template>
