<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cagdqbcef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cagdqbcef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:document-x-mark-solid" /></template>
