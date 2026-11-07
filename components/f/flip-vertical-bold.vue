<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb-4crb9y.css';
import '../../css/g/gydy3ndrg.css';
import '../../css/r/re_l3eb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb-4crb9y"/><path class="gydy3ndrg"/><path clip-rule="evenodd" class="re_l3eb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-vertical-bold" /></template>
