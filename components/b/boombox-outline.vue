<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-0pgab_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-0pgab_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:boombox-outline" /></template>
