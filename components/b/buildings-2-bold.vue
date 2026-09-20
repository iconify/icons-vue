<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3no70bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3no70bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-2-bold" /></template>
