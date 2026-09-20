<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if1fl5uuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="if1fl5uuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:headphone-1" /></template>
