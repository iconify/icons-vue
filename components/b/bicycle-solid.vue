<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2jzf1b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a2jzf1b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bicycle-solid" /></template>
