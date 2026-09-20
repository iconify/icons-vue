<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk10n7b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk10n7b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:filter-list-duotone" /></template>
