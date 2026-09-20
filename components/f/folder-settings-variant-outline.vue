<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4tqrxz6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4tqrxz6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-settings-variant-outline" /></template>
