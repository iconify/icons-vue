<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skiv409wp.css';
import '../../css/v/v5f6axbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skiv409wp"/><path class="v5f6axbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-arrow-left-duotone" /></template>
