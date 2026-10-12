<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l43uzl-6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l43uzl-6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:face-neutral-filled" /></template>
