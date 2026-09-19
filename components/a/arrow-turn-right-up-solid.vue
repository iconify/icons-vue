<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcwmwoozx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bcwmwoozx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-right-up-solid" /></template>
