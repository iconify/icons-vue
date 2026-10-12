<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aftq99syt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aftq99syt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ev-charger-filled" /></template>
