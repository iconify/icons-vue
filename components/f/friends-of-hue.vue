<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk-vg6ler.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk-vg6ler"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:friends-of-hue" /></template>
