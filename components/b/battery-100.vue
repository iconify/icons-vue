<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8gjc9qvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8gjc9qvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:battery-100" /></template>
