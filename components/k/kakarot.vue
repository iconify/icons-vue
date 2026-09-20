<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5kpf_bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5kpf_bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kakarot" /></template>
