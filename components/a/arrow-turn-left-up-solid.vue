<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgd2j9bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgd2j9bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-left-up-solid" /></template>
