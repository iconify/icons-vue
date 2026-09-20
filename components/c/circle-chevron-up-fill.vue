<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxk2rigpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxk2rigpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevron-up-fill" /></template>
