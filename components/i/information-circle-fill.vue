<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if9an1bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if9an1bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:information-circle-fill" /></template>
