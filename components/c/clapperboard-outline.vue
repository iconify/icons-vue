<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcj0pibjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcj0pibjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-outline" /></template>
