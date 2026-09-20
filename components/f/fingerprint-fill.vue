<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onocauoox.css';
import '../../css/l/lpwvf4b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onocauoox"/><path class="lpwvf4b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fingerprint-fill" /></template>
