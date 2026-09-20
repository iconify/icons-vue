<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veo2_hbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="veo2_hbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:incognito-outline" /></template>
