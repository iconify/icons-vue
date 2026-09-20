<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djck3bcpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djck3bcpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:clock-light" /></template>
