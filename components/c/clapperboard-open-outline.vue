<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi-ilqbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bi-ilqbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-open-outline" /></template>
