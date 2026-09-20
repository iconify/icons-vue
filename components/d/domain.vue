<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgnnlyb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgnnlyb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:domain" /></template>
