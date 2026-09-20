<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ead2_1bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ead2_1bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-outline" /></template>
