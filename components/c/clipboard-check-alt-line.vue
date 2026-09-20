<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr-0gy2dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr-0gy2dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-check-alt-line" /></template>
