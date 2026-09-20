<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shb1edcff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shb1edcff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:home-fill" /></template>
